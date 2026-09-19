<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k327wib4f.css';
import '../../css/t/t6tpgmbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k327wib4f"/><path class="t6tpgmbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fork-repo" /></template>
