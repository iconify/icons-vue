<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9cehxl3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9cehxl3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-charging-2" /></template>
