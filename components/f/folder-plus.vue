<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nog_us2ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nog_us2ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:folder-plus" /></template>
