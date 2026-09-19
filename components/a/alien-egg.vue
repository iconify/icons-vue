<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b261mqb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b261mqb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:alien-egg" /></template>
