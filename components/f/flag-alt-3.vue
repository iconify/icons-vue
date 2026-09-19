<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9h68pkmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9h68pkmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flag-alt-3" /></template>
