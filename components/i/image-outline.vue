<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h909b4b3w.css';
import '../../css/f/fzhx4wbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h909b4b3w"/><circle class="fzhx4wbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:image-outline" /></template>
