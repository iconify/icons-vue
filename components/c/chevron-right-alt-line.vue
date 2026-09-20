<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed_ztubpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed_ztubpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-right-alt-line" /></template>
