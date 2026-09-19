<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8krpkbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i8krpkbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-fn-small" /></template>
