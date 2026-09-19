<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2iukbb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2iukbb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-pie-alt-02" /></template>
