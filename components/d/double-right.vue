<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9j7mqbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x9j7mqbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:double-right" /></template>
