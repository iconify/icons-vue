<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk5yd9wru.css';
import '../../css/y/ygr19icki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dk5yd9wru"/><path clip-rule="evenodd" class="ygr19icki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-start-16" /></template>
