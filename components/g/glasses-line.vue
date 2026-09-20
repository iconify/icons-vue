<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afqh7e3uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afqh7e3uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:glasses-line" /></template>
