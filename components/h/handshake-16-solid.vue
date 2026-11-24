<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqf2w1bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mqf2w1bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:handshake-16-solid" /></template>
