<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8zs4bbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8zs4bbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:down-two-headed-line" /></template>
