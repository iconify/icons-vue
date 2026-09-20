<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvk04dbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvk04dbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-move-vertical" /></template>
