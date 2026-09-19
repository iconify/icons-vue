<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3ozll52o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b3ozll52o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:foot-trip" /></template>
