<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbo1zab8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sbo1zab8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:archive" /></template>
