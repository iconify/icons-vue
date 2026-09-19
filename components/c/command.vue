<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gre2h1byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gre2h1byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:command" /></template>
