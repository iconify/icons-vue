<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9yq2q4xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9yq2q4xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark" /></template>
