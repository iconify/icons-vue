<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft85d9bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft85d9bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-objects-vertical-center" /></template>
