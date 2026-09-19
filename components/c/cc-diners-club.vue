<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vym9ewb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vym9ewb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cc-diners-club" /></template>
