<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxqk6110f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxqk6110f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:magnifying-glass-plus" /></template>
