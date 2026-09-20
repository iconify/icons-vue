<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdhb7_b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kdhb7_b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-to-banknote-in-slot" /></template>
