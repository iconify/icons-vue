<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lddcg3b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lddcg3b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:align-left" /></template>
