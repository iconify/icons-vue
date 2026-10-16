<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqfw9ounj.css';
import '../../css/i/ibxubn_yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gqfw9ounj"/><path class="ibxubn_yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dehumidifier-20" /></template>
