<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx37qqbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx37qqbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-solid" /></template>
