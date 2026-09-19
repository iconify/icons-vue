<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml0qg9bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="ml0qg9bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bell-alt" /></template>
