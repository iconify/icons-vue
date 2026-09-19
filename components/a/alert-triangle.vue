<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2l_fnbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2l_fnbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:alert-triangle" /></template>
