<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdywcgtaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdywcgtaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:clipboard-2-fill" /></template>
