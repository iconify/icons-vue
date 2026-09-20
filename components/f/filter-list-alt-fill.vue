<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek9th_bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek9th_bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:filter-list-alt-fill" /></template>
