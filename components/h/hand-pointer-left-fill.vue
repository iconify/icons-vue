<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7xi6581l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7xi6581l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-left-fill" /></template>
