<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa46xtaxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa46xtaxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-2" /></template>
