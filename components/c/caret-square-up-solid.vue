<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a59iyablm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a59iyablm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:caret-square-up-solid" /></template>
