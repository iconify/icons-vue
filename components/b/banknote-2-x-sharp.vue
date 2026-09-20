<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u970n0bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u970n0bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-x-sharp" /></template>
