<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be4ocjgyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="be4ocjgyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:emote-happy" /></template>
