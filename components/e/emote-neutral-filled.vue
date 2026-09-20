<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0jw2wlab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="i0jw2wlab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:emote-neutral-filled" /></template>
