<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knt09wfpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knt09wfpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:battery-empty" /></template>
