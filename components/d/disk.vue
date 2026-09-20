<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1o7qhb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m1o7qhb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:disk" /></template>
