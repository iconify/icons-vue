<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr13r5e0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr13r5e0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:fast-rewind-outline" /></template>
