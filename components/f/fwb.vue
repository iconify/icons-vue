<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqgn4zb9y.css';
import '../../css/i/i2zu83iwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqgn4zb9y"/><path class="i2zu83iwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fwb" /></template>
