<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7zwcqbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7zwcqbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:glm" /></template>
