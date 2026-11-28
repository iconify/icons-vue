<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu1lk149i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu1lk149i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:case-sensitive-solid" /></template>
