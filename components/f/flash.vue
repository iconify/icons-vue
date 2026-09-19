<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo10oacue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="mo10oacue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:flash" /></template>
