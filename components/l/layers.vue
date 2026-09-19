<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-dmpsp-p.css';
import '../../css/e/eeukgofxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-dmpsp-p"/><path class="eeukgofxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:layers" /></template>
