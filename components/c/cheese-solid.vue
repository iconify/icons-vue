<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqk4_wbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqk4_wbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cheese-solid" /></template>
