<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyoixcc3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyoixcc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-file-text" /></template>
