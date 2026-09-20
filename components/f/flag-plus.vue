<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if5c0vbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if5c0vbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-plus" /></template>
