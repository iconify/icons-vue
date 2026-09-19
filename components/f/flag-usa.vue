<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4zlantmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="v4zlantmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:flag-usa" /></template>
