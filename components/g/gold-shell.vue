<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo9_5wbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo9_5wbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gold-shell" /></template>
