<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u40po5pyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u40po5pyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-outline" /></template>
