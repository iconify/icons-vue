<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9kw14ayb.css';
import '../../css/w/wzt-b-bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="q9kw14ayb"/><rect class="wzt-b-bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:columns-filled" /></template>
