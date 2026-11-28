<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovf2uynpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovf2uynpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fire-extinguisher" /></template>
