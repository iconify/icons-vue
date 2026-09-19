<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klvyo3bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="klvyo3bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:cellphone" /></template>
