<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il1kkqbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="il1kkqbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dashboard-circle-solid" /></template>
