<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz89a7_fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz89a7_fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:crown-b" /></template>
