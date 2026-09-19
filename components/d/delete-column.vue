<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj-zn2xho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-zn2xho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:delete-column" /></template>
