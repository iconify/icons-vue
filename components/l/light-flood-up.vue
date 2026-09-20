<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8s_3uboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8s_3uboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:light-flood-up" /></template>
