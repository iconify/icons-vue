<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp8cedcrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tp8cedcrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alexandrie-light" /></template>
