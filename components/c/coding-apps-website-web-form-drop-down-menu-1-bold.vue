<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-2o90bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-2o90bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coding-apps-website-web-form-drop-down-menu-1-bold" /></template>
