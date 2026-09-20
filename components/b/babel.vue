<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irrpp75oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irrpp75oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:babel" /></template>
