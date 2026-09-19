<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/y3bs4jbfx.css';
import '../../css/q/qknhedbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="edit-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="y3bs4jbfx"/><path class="qknhedbtq"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:edit-outline" /></template>
