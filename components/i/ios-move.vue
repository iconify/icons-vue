<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qir54xchq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qir54xchq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-move" /></template>
