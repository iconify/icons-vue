<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl_yqglbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl_yqglbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image" /></template>
