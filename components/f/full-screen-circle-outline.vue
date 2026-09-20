<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v49232f_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v49232f_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-circle-outline" /></template>
