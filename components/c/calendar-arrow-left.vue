<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apn_b4pdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apn_b4pdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-arrow-left" /></template>
