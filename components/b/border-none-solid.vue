<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqw920b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="eqw920b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-none-solid" /></template>
