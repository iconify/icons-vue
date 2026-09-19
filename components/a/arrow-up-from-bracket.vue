<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkmwn-55o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pkmwn-55o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-from-bracket" /></template>
