<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh9lg8b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":401,"height":401};
const content = `<path class="bh9lg8b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deno-light" /></template>
