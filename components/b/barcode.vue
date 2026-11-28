<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubdmll87o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubdmll87o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:barcode" /></template>
