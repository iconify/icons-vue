<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtq1sib7y.css';
import '../../css/p/puz5jibvr.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vtq1sib7y"/><path class="puz5jibvr"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-check-20" /></template>
