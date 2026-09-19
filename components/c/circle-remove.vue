<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcl5t7bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="bcl5t7bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-remove" /></template>
