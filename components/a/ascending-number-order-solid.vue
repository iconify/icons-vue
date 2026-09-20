<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etnxx7kib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="etnxx7kib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ascending-number-order-solid" /></template>
