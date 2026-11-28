<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr6kczzpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr6kczzpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:kick-scooter" /></template>
