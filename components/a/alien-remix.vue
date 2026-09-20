<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7o2qq6oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a7o2qq6oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:alien-remix" /></template>
