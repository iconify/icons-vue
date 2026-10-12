<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-82q3kkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-82q3kkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:droplet-off-filled" /></template>
