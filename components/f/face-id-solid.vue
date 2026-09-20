<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwrbb51dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwrbb51dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:face-id-solid" /></template>
