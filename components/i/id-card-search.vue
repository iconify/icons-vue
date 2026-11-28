<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwrrb6bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwrrb6bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:id-card-search" /></template>
