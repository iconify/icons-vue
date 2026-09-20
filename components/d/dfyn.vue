<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo78nybtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo78nybtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dfyn" /></template>
