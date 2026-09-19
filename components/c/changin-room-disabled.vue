<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfdlwqbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfdlwqbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:changin-room-disabled" /></template>
