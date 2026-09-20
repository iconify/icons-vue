<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t18qekbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t18qekbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:concierge-bell" /></template>
