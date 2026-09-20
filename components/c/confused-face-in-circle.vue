<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8-7bccmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m8-7bccmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:confused-face-in-circle" /></template>
