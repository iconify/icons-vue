<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fujslo8xa.css';
import '../../css/h/hchurepih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fujslo8xa"/><path class="hchurepih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:badge-dollar-light" /></template>
