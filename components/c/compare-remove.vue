<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7-dn10az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7-dn10az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:compare-remove" /></template>
