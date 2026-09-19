<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcv3g-l2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pcv3g-l2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-square-fill" /></template>
