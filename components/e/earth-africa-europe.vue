<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_4g7047h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_4g7047h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:earth-africa-europe" /></template>
