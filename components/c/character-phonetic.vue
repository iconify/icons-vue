<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hulotdbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hulotdbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:character-phonetic" /></template>
