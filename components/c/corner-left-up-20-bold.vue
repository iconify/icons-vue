<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afkvrrboz.css';
import '../../css/q/qekqfrbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="afkvrrboz"/><path class="qekqfrbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-left-up-20-bold" /></template>
