<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj4hj9b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tj4hj9b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-3-trianglepath" /></template>
