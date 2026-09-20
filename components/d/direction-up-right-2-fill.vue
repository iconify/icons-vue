<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knti61bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knti61bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:direction-up-right-2-fill" /></template>
