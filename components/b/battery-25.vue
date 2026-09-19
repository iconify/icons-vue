<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp-udmb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tp-udmb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:battery-25" /></template>
