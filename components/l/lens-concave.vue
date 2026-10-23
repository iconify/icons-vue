<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezcs8yb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezcs8yb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:lens-concave" /></template>
