<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm_umbc-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pm_umbc-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ball-solid" /></template>
