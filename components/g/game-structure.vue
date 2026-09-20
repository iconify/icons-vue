<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m05bd9i9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m05bd9i9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:game-structure" /></template>
