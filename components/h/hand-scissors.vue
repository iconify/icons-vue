<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp-_iwjua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pp-_iwjua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-scissors" /></template>
