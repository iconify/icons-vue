<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2c-tw1rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2c-tw1rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:docker-logo-solid" /></template>
