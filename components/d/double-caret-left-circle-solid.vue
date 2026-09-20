<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs08r5bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rs08r5bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-left-circle-solid" /></template>
