<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_uj--bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_uj--bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-tabs" /></template>
