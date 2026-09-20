<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtm8l_bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wtm8l_bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:it-glue-dark" /></template>
