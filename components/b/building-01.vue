<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oovfznbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oovfznbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:building-01" /></template>
