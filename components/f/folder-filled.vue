<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1uunhuff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1uunhuff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-filled" /></template>
