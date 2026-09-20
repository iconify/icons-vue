<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl3m4qsnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rl3m4qsnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-right-duotone" /></template>
