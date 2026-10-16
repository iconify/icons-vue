<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr83kubtu.css';
import '../../css/f/fyjv8ddts.css';
import '../../css/x/x5aslfb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gr83kubtu"/><path class="fyjv8ddts"/><path class="x5aslfb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:agv-20-bold" /></template>
