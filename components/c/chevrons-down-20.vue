<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deisahb9j.css';
import '../../css/b/bfngflyuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="deisahb9j"/><path class="bfngflyuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-down-20" /></template>
