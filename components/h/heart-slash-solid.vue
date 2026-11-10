<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eilcihlxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eilcihlxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heart-slash-solid" /></template>
