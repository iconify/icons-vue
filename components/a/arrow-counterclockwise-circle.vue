<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pspf4cc1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pspf4cc1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-counterclockwise-circle" /></template>
