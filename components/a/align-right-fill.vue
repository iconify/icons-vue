<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcgt-94-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcgt-94-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-right-fill" /></template>
