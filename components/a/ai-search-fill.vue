<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgej7mwsz.css';
import '../../css/y/ysf6s1bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgej7mwsz"/><path class="ysf6s1bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-search-fill" /></template>
