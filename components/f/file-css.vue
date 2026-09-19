<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd2ryx8bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd2ryx8bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-css" /></template>
