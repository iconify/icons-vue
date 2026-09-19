<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-dmpsp-p.css';
import '../../css/n/n2fkhdu9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-dmpsp-p"/><path class="n2fkhdu9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:layers-external" /></template>
