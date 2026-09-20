<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_cz6xddp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_cz6xddp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-check-outline" /></template>
