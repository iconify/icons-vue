<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkb7t_bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkb7t_bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:helium-tot" /></template>
