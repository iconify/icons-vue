<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcrvpl9sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcrvpl9sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:barcode-filled" /></template>
