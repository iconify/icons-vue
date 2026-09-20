<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmqur-wjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmqur-wjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:file-import" /></template>
