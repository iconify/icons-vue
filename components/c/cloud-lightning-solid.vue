<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua6xqgsfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua6xqgsfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-lightning-solid" /></template>
