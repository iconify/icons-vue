<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul8j8_bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul8j8_bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:drugs-cannabis" /></template>
