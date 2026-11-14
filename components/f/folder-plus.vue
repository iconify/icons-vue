<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhi8vggfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhi8vggfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-plus" /></template>
