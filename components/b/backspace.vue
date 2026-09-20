<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi476qegc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi476qegc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:backspace" /></template>
