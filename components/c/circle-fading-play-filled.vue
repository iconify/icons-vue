<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arhhw8bcu.css';
import '../../css/a/aiztnfbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arhhw8bcu"/><path class="aiztnfbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-fading-play-filled" /></template>
