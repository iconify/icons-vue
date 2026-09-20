<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0qphggqc.css';
import '../../css/j/jnqqvnouk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0qphggqc"/><path class="jnqqvnouk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:doc2x" /></template>
