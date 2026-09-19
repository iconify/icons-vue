<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex_pl8bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ex_pl8bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:gopuram" /></template>
