<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sezvypuah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sezvypuah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:battery-100" /></template>
