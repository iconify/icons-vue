<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v158v1j5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v158v1j5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hungry" /></template>
