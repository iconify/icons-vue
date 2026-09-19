<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0q3nubrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p0q3nubrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lefthandphone" /></template>
