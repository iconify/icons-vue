<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojjrbdc4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":781};
const content = `<path class="ojjrbdc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:6" /></template>
