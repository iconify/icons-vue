<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5amaac0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="q5amaac0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-vertical-solid" /></template>
