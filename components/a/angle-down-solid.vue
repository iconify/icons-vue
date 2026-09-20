<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-e96khov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-e96khov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-down-solid" /></template>
