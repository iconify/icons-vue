<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe09b3bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe09b3bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-redo-bold" /></template>
