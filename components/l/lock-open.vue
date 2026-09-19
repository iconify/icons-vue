<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5pd71w6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c5pd71w6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-open" /></template>
