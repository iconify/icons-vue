<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wruy1ebcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wruy1ebcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-waves-solid" /></template>
