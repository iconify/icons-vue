<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfnyr6eve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfnyr6eve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:database-arrow-up" /></template>
