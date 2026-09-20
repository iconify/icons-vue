<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6-5yob4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6-5yob4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:domain-switch" /></template>
