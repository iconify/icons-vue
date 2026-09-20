<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn__gvaae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn__gvaae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-move-filled" /></template>
