<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu-hd0b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu-hd0b9t primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:command-duotone" /></template>
