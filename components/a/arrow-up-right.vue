<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmb_b6brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmb_b6brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-right" /></template>
