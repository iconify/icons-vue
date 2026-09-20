<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co3ix1bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="co3ix1bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:info-multiple" /></template>
