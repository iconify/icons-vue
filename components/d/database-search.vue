<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxw2rj-de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxw2rj-de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:database-search" /></template>
