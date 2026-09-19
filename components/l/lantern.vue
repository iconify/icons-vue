<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skc67joyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skc67joyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lantern" /></template>
