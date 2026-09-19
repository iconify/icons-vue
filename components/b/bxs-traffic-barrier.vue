<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg4na6bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg4na6bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-traffic-barrier" /></template>
