<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku_it8bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku_it8bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:email-fill" /></template>
