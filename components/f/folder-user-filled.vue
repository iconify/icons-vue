<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5at6trmc.css';
import '../../css/i/i669q6bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5at6trmc"/><path class="i669q6bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-user-filled" /></template>
