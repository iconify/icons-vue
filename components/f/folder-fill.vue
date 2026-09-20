<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg9yb5n6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg9yb5n6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-fill" /></template>
