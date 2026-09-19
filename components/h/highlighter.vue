<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at2p-abdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":544,"height":512};
const content = `<path class="at2p-abdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:highlighter" /></template>
