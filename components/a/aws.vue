<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8sowac7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":480};
const content = `<path class="q8sowac7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:aws" /></template>
