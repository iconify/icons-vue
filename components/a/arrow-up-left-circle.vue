<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_w-bcps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="el_w-bcps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-left-circle" /></template>
