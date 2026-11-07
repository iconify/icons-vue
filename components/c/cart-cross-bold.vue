<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njrvemoot.css';
import '../../css/u/ujd91437t.css';
import '../../css/d/d6h3j5b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="njrvemoot"/><path class="ujd91437t"/><path class="d6h3j5b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-cross-bold" /></template>
