<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p12_vcctc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="p12_vcctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gramophone" /></template>
