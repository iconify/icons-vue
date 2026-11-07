<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo7u7db2l.css';
import '../../css/t/t5k-_f5ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo7u7db2l"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-up-outline" /></template>
