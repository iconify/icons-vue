<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3z3v4axp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="l3z3v4axp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-compact-right" /></template>
