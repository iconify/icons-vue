<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od7oqmbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="od7oqmbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-outline" /></template>
