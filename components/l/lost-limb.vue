<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug78cmbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ug78cmbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lost-limb" /></template>
