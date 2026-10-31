<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t71s4gkgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t71s4gkgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-chevron-right-gloss" /></template>
