<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o361ukbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o361ukbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dollar-alt-2-line" /></template>
