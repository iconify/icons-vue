<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2-p4bcnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2-p4bcnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:briefcase-solid" /></template>
