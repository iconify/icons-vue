<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wchz1fbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wchz1fbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bag-badge-minus" /></template>
