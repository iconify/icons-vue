<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux94p3bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ux94p3bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:link-broken" /></template>
