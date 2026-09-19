<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btxd_x04d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="btxd_x04d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lyre" /></template>
