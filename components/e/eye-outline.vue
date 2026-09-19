<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjhtbdckh.css';
import '../../css/a/a7ajif61p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yjhtbdckh"/><circle class="a7ajif61p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:eye-outline" /></template>
