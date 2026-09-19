<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nso-0gb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nso-0gb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:juggling-seal" /></template>
