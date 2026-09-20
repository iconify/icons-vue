<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glqc0ohwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glqc0ohwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:barcode-1" /></template>
