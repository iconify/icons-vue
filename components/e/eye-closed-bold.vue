<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4fgxwb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4fgxwb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-closed-bold" /></template>
