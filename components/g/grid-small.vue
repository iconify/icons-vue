<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfs4r6bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfs4r6bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:grid-small" /></template>
