<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrgr0mbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lrgr0mbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:delta-chat-light" /></template>
