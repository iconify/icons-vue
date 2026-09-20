<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk-6u-b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hk-6u-b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:keyboard" /></template>
