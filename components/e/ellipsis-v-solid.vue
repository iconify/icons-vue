<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4f85kbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4f85kbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:ellipsis-v-solid" /></template>
