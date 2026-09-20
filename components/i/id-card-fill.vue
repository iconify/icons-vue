<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct_lf2gmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct_lf2gmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-card-fill" /></template>
