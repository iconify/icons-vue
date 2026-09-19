<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb870rb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qb870rb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:heart-circle-fill" /></template>
