<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4upzqbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4upzqbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fishaudio" /></template>
