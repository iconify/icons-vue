<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui3celb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ui3celb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:laptop" /></template>
