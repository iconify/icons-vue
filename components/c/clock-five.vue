<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cep2c0bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cep2c0bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:clock-five" /></template>
