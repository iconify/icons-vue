<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_shecbdt.css';
import '../../css/w/wodq73bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="n_shecbdt"/><path clip-rule="evenodd" class="wodq73bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:indent" /></template>
