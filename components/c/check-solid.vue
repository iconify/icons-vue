<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2gbr2b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2gbr2b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-solid" /></template>
