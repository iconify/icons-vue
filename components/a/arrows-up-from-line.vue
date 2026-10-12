<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uralp8bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uralp8bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-up-from-line" /></template>
