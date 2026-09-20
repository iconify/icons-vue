<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr5qf2b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="tr5qf2b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:fullbattery" /></template>
