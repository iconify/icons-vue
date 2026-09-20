<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7kigfbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7kigfbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:electricity-fill" /></template>
