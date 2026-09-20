<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wez0f6e8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wez0f6e8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-outer-solid" /></template>
