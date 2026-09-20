<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1ucqd-cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1ucqd-cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alarm-clock-minus-sharp" /></template>
