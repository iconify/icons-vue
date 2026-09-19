<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt8f_wtrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rt8f_wtrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-up-square" /></template>
