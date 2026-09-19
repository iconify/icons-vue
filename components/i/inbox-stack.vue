<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ausqiqdld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ausqiqdld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:inbox-stack" /></template>
