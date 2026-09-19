<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfamsoo7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dfamsoo7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-down-circle-fill" /></template>
