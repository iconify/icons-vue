<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6dt2jltz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="p6dt2jltz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left" /></template>
