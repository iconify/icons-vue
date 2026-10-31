<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwbo4nbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwbo4nbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:facebook-round" /></template>
