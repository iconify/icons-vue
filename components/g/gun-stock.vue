<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh3a-cbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oh3a-cbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gun-stock" /></template>
