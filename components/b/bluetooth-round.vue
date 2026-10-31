<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbev39b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbev39b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bluetooth-round" /></template>
