<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2xsgrbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o2xsgrbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:life-ring" /></template>
