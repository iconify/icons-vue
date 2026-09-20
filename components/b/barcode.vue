<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bich7zbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bich7zbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:barcode" /></template>
