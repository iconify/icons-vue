<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/codtw1b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="codtw1b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:error-multiple-filled" /></template>
