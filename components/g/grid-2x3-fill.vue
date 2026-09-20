<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elqhvcgnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="elqhvcgnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x3-fill" /></template>
