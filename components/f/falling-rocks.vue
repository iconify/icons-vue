<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1u3g-62o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p1u3g-62o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:falling-rocks" /></template>
