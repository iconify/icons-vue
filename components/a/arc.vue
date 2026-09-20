<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s87um7a2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s87um7a2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arc" /></template>
