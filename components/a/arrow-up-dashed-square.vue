<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qodrpn5hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qodrpn5hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-up-dashed-square" /></template>
