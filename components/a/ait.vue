<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-yalvqiy.css';
import '../../css/k/kj3mfibmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-yalvqiy"/><path class="kj3mfibmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ait" /></template>
