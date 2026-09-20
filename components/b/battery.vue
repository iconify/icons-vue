<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eceoyuoqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="eceoyuoqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:battery" /></template>
