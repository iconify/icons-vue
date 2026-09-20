<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c55_stbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c55_stbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-right-sharp-fill" /></template>
