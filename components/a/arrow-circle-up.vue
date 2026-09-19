<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak_owkqcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak_owkqcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-circle-up" /></template>
