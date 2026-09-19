<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxdpf6bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zxdpf6bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:command-line-16-solid" /></template>
