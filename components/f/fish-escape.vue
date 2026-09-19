<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phau6domw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phau6domw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fish-escape" /></template>
