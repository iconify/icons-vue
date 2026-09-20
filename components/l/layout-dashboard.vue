<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdq5h-b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdq5h-b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-dashboard" /></template>
