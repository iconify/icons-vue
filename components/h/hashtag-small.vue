<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rigfyab2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rigfyab2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hashtag-small" /></template>
