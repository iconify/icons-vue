<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmwk8k2ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmwk8k2ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:like-solid" /></template>
