<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc7z9jb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc7z9jb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cafe" /></template>
