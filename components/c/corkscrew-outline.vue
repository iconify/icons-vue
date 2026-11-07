<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ug3crng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-ug3crng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:corkscrew-outline" /></template>
