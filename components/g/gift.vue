<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8ar4sc7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o8ar4sc7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:gift" /></template>
