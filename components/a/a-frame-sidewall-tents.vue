<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9jr-rb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c9jr-rb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:a-frame-sidewall-tents" /></template>
