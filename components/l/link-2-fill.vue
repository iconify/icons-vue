<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-gpmsb9n.css';
import '../../css/m/mdn6n1b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-gpmsb9n"/><path class="mdn6n1b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:link-2-fill" /></template>
