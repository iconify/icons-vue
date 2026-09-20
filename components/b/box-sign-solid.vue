<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt5_813gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gt5_813gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:box-sign-solid" /></template>
