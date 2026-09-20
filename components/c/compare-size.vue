<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfe-3o5hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfe-3o5hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:compare-size" /></template>
