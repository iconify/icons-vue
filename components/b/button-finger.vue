<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlrh10o5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dlrh10o5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:button-finger" /></template>
