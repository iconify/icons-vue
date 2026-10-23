<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba-w97ous.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-w97ous"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-plus" /></template>
