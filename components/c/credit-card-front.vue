<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5j6r5bas.css';
import '../../css/k/kj3cr3nbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5j6r5bas"/><path class="kj3cr3nbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:credit-card-front" /></template>
