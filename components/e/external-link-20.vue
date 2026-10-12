<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqu6-wf_q.css';
import '../../css/f/f4sd7-1jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dqu6-wf_q"/><path class="f4sd7-1jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:external-link-20" /></template>
