<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qim_7oblv.css';
import '../../css/a/as36oyixv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qim_7oblv"/><path class="as36oyixv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cog-light" /></template>
