<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uak386bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uak386bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-stop" /></template>
