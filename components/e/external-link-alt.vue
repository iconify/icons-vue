<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emcz-1bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emcz-1bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:external-link-alt" /></template>
