<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf1qxsb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1qxsb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-three-eighth-solid" /></template>
