<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4nv0bbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4nv0bbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-bottombar-inactive" /></template>
