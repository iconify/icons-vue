<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw7wxvlhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uw7wxvlhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-up-circle-fill" /></template>
