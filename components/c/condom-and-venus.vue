<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lda7zbb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lda7zbb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:condom-and-venus" /></template>
