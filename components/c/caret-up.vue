<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arv9ch36c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="arv9ch36c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:caret-up" /></template>
