<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl91i5v9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl91i5v9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-round-minimalistic-bold" /></template>
