<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9dj_bc_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9dj_bc_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:envelope" /></template>
