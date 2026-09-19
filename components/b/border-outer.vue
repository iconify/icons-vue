<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz0bikexj.css';
import '../../css/a/an2--ubjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nz0bikexj"/><path class="an2--ubjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:border-outer" /></template>
