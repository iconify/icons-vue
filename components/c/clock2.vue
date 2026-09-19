<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4iv2zb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s4iv2zb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:clock2" /></template>
