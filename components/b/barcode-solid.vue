<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nedchvb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nedchvb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:barcode-solid" /></template>
