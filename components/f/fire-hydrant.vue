<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abnde_b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abnde_b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fire-hydrant" /></template>
