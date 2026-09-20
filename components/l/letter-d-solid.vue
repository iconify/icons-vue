<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrb84qb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrb84qb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-d-solid" /></template>
