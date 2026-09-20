<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km1o2r7do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km1o2r7do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-8-filled" /></template>
