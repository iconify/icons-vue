<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeb407i0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xeb407i0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:audio-cable-solid" /></template>
