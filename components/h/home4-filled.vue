<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3nji1znv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r3nji1znv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home4-filled" /></template>
