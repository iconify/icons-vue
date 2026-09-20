<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt1q18taj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rt1q18taj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arcane-dark" /></template>
