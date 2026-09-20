<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw2v_fbbh.css';
import '../../css/g/gu10zdn1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw2v_fbbh"/><path class="gu10zdn1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:file-duotone" /></template>
