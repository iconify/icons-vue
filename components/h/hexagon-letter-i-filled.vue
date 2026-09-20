<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgm81wbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgm81wbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-i-filled" /></template>
