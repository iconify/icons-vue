<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixr32ep7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixr32ep7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-plus-fill" /></template>
