<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm8o83l5u.css';
import '../../css/a/ajmi_0bqu.css';
import '../../css/d/djpikibkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rm8o83l5u"/><path class="ajmi_0bqu"/><path class="djpikibkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-leak-20-bold" /></template>
