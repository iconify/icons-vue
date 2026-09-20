<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scv5m7bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scv5m7bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:indifferent-ghost-solid" /></template>
