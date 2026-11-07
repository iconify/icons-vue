<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljfitzhle.css';
import '../../css/r/r90ig9mfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljfitzhle"/><path class="r90ig9mfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dislike-bold" /></template>
