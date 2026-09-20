<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5ousf9rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g5ousf9rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-pause-2" /></template>
