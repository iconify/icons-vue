<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w61psqb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w61psqb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:envelope-badge" /></template>
