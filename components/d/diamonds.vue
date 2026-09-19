<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzt3akbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzt3akbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:diamonds" /></template>
