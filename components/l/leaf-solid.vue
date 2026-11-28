<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnstc0q8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnstc0q8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:leaf-solid" /></template>
