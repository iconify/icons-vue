<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-viribkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n-viribkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:deno-outline" /></template>
