<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rme7j1bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="rme7j1bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:adn" /></template>
