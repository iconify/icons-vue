<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0gvw96fa.css';
import '../../css/h/hw9ee6laf.css';
import '../../css/a/aitp4sbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0gvw96fa"/><path class="hw9ee6laf"/><path clip-rule="evenodd" class="aitp4sbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-outline" /></template>
