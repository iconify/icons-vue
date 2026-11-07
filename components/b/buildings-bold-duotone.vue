<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2j11xx0i.css';
import '../../css/f/ft03l-j3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2j11xx0i"/><path class="ft03l-j3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-bold-duotone" /></template>
