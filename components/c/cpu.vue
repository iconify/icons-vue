<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp606zbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="rp606zbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cpu" /></template>
