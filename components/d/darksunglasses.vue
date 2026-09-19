<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2w7w-b-w.css';
import '../../css/q/q49xs08qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2w7w-b-w"/><path class="q49xs08qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:darksunglasses" /></template>
