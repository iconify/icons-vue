<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iji9n2szv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iji9n2szv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fireflake" /></template>
