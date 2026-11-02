<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdi86dvjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdi86dvjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-circle-fill" /></template>
