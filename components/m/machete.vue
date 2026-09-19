<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or4ad2bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="or4ad2bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:machete" /></template>
