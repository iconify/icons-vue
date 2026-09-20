<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z69k53r8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z69k53r8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:counting-4" /></template>
