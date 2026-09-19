<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqgyk5b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqgyk5b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-top" /></template>
