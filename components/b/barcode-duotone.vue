<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugj8ebreh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ugj8ebreh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:barcode-duotone" /></template>
