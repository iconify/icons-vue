<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qej8iv7_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qej8iv7_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-difference-outline" /></template>
