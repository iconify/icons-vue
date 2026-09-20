<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7z-gpbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7z-gpbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-right-light" /></template>
