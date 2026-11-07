<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it-6mlbhr.css';
import '../../css/b/bckx04b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it-6mlbhr"/><path clip-rule="evenodd" class="bckx04b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:backpack-outline" /></template>
