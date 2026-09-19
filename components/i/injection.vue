<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v365mbciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v365mbciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:injection" /></template>
