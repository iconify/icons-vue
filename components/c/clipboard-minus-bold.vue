<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuay936ng.css';
import '../../css/c/c4946-17v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kuay936ng"/><path class="c4946-17v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-minus-bold" /></template>
