<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxa_ly2fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sxa_ly2fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlej" /></template>
