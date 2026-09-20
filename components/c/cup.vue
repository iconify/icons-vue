<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhphg8fnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhphg8fnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cup" /></template>
