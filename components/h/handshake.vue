<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc23b6dos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rc23b6dos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:handshake" /></template>
