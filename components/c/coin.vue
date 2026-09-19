<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3tn8drin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c3tn8drin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:coin" /></template>
