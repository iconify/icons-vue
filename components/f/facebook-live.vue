<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txqp9v-bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txqp9v-bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:facebook-live" /></template>
