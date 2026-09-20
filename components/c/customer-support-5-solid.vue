<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii30u3bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ii30u3bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:customer-support-5-solid" /></template>
