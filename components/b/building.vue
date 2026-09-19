<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwb2ofesw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwb2ofesw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:building" /></template>
