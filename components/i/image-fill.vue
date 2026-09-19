<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n90k4bjti.css';
import '../../css/f/fzhx4wbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n90k4bjti"/><circle class="fzhx4wbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:image-fill" /></template>
