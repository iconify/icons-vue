<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6m0gsbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6m0gsbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-3-bold" /></template>
