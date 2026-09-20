<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6iuz7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6iuz7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:lift-1-bold" /></template>
