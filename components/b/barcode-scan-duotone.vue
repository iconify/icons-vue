<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxobjqb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxobjqb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:barcode-scan-duotone" /></template>
