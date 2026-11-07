<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbi9b4b7j.css';
import '../../css/a/atape3b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbi9b4b7j"/><path clip-rule="evenodd" class="atape3b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-bold" /></template>
