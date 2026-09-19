<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcvuivbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wcvuivbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:chafing-dish-one" /></template>
