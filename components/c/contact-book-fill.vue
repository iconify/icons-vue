<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sktthrbsc.css';
import '../../css/c/cxl-8rb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sktthrbsc"/><path class="cxl-8rb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:contact-book-fill" /></template>
