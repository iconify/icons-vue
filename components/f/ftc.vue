<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcitvccga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcitvccga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ftc" /></template>
