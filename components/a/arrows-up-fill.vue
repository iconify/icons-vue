<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7xgfjbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7xgfjbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-up-fill" /></template>
