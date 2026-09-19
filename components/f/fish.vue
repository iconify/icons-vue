<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp9s_mb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="pp9s_mb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fish" /></template>
