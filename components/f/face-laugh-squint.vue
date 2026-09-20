<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjngycc7b.css';
import '../../css/o/ooafjrbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjngycc7b"/><path class="ooafjrbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-laugh-squint" /></template>
