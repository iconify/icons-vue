<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1atvnm2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1atvnm2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:inbox-plus-solid" /></template>
