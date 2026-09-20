<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmh3rlnos.css';
import '../../css/d/dazc8w85q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmh3rlnos"/><path class="dazc8w85q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-arrow-up" /></template>
