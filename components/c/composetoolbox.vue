<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3e4etbxf.css';
import '../../css/j/jgee_j83r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3e4etbxf"/><path class="jgee_j83r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composetoolbox" /></template>
