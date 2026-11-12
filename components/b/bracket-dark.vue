<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr-iiqyqg.css';
import '../../css/f/f6p_znbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rr-iiqyqg"/><path class="f6p_znbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bracket-dark" /></template>
