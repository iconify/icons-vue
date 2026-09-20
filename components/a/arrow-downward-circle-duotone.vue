<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmnjdabrt.css';
import '../../css/o/odh8gnbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmnjdabrt"/><path class="odh8gnbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-downward-circle-duotone" /></template>
