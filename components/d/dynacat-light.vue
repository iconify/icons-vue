<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbu9dvbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbu9dvbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynacat-light" /></template>
