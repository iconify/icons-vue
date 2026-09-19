<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg6mswtmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dg6mswtmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt" /></template>
