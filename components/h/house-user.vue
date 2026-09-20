<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v51u0wbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v51u0wbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:house-user" /></template>
