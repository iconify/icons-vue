<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk2xqnyxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk2xqnyxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folders" /></template>
