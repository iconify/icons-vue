<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_t18m0xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_t18m0xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:longer" /></template>
