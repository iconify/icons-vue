<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fas4occ8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fas4occ8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bloglovin" /></template>
