<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ellay1bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1280};
const content = `<path class="ellay1bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:genderless" /></template>
