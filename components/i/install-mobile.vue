<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjn59jb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjn59jb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:install-mobile" /></template>
