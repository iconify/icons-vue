<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsf8c2b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsf8c2b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit" /></template>
