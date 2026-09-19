<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv5nqnbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jv5nqnbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magic-lamp" /></template>
