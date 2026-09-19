<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxg65syqu.css';
import '../../css/b/b0dccwb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxg65syqu"/><path class="b0dccwb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:channel-filled" /></template>
