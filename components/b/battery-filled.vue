<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaeket_ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaeket_ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-filled" /></template>
