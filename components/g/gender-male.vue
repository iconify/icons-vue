<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poxw_gbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poxw_gbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:gender-male" /></template>
