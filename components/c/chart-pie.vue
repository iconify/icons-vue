<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6jhl1jki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6jhl1jki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:chart-pie" /></template>
