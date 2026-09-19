<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytmvb327i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytmvb327i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hash" /></template>
