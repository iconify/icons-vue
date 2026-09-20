<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwedw0bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bwedw0bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hospital-filled" /></template>
