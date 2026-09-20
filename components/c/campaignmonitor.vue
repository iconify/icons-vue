<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlj_3z6ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlj_3z6ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:campaignmonitor" /></template>
