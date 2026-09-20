<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmln_jmlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmln_jmlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-off" /></template>
