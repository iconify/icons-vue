<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rto219pbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rto219pbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-2" /></template>
