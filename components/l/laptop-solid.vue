<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acui1gbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acui1gbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:laptop-solid" /></template>
