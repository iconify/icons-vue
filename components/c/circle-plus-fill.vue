<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9y182zmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9y182zmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-plus-fill" /></template>
