<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1j59_5rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l1j59_5rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blacklargesquare" /></template>
