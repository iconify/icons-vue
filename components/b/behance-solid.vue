<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5-r2cb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="q5-r2cb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:behance-solid" /></template>
