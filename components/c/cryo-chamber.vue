<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk8gq0ufp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bk8gq0ufp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cryo-chamber" /></template>
