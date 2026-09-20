<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky8l_-t4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky8l_-t4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:magnet-left" /></template>
