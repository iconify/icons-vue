<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgqfhn5ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgqfhn5ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:infinity-outline" /></template>
