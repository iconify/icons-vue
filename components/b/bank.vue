<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivanhnbdc.css';
import '../../css/q/q-befwo0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivanhnbdc"/><path class="q-befwo0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bank" /></template>
