<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfj7c24mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfj7c24mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-3-fill" /></template>
