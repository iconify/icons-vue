<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foa7u6bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foa7u6bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:circle-dashed-solid" /></template>
