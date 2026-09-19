<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1mt0n45y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="a1mt0n45y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:clock" /></template>
