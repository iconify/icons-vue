<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ledfk4o7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ledfk4o7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-open-filled" /></template>
