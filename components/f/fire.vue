<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7e5m7b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7e5m7b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:fire" /></template>
