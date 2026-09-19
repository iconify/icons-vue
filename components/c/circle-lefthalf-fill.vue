<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3khy7bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u3khy7bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:circle-lefthalf-fill" /></template>
