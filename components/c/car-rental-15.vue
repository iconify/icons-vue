<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxyl2pbba.css';
import '../../css/m/m-7so2bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wxyl2pbba"/><path class="m-7so2bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car-rental-15" /></template>
