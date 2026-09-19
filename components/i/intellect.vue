<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktxbgbbpn.css';
import '../../css/y/y3f_nfkuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktxbgbbpn"/><path class="y3f_nfkuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:intellect" /></template>
