<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8zje8b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8zje8b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-left-circle-fill" /></template>
