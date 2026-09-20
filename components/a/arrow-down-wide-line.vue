<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_r_nr3jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_r_nr3jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-wide-line" /></template>
