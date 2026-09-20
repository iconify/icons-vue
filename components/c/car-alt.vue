<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_ri79bak.css';
import '../../css/s/sl-mdjb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w_ri79bak"/><path class="sl-mdjb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:car-alt" /></template>
