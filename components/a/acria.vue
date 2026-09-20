<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p763z8ceo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p763z8ceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:acria" /></template>
