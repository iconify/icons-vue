<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk6o67b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pk6o67b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-doc" /></template>
