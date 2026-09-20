<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4-z3mbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4-z3mbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bulwark-dark" /></template>
