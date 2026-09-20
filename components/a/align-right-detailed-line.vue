<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd_-2rbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_-2rbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-right-detailed-line" /></template>
