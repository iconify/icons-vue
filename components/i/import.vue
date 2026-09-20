<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8qkxmpel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8qkxmpel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:import" /></template>
