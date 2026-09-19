<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktxbgbbpn.css';
import '../../css/b/b8mhmhbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktxbgbbpn"/><path class="b8mhmhbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cognition" /></template>
