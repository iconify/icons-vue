<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjl0uebbh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLXXc1GxT"><path class="yjl0uebbh"/></mask></defs><path mask="url(#SVGLXXc1GxT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bookshelf" /></template>
