<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmd42x_uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cmd42x_uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:lock-key-filled" /></template>
