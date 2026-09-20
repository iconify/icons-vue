<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci9vmlb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci9vmlb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-add-line" /></template>
