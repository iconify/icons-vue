<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr03lx9eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fr03lx9eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:formula" /></template>
