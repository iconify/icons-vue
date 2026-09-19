<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzyi55b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzyi55b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-rust" /></template>
