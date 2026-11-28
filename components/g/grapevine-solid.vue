<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-9ts-tho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-9ts-tho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grapevine-solid" /></template>
