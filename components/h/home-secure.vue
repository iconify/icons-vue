<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s524j1nso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s524j1nso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-secure" /></template>
