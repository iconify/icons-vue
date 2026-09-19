<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg8ren7cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cg8ren7cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:largeorangediamond" /></template>
