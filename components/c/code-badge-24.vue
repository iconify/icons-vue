<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx01pybcw.css';
import '../../css/g/go6el9bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx01pybcw"/><path class="go6el9bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-badge-24" /></template>
