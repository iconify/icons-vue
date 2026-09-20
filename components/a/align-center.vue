<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocaehubvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ocaehubvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:align-center" /></template>
