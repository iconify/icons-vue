<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5hp_4bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5hp_4bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-zoom-in-outline" /></template>
