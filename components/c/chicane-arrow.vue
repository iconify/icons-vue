<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caizf_bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="caizf_bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:chicane-arrow" /></template>
