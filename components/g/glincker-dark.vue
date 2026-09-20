<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar1skxb1o.css';
import '../../css/q/q35s5pbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":375,"height":375};
const content = `<path class="ar1skxb1o"/><path class="q35s5pbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:glincker-dark" /></template>
