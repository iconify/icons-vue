<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7nsomhyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7nsomhyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-yen-solid" /></template>
