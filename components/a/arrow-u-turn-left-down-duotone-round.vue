<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8bof-icw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8bof-icw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-left-down-duotone-round" /></template>
