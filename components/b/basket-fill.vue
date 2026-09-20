<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_1-4s6ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_1-4s6ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:basket-fill" /></template>
