<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s338b9bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s338b9bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:barcode-outline" /></template>
