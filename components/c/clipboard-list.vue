<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laczu_kou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="laczu_kou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clipboard-list" /></template>
