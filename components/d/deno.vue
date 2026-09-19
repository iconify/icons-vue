<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-vvoub4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-vvoub4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:deno" /></template>
