<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkwaqebax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rkwaqebax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bar-chair-outline" /></template>
