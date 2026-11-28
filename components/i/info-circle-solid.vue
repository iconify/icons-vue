<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh9n0ccen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9n0ccen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:info-circle-solid" /></template>
