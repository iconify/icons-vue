<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obr3sqb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obr3sqb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:bolt-b" /></template>
