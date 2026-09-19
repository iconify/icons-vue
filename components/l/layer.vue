<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulc-50zkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulc-50zkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:layer" /></template>
