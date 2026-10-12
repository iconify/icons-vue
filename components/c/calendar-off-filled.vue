<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6i2hsbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6i2hsbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-off-filled" /></template>
