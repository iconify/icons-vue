<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eho7rebzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eho7rebzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:barcode-gloss" /></template>
