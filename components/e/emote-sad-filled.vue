<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp_ldxbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vp_ldxbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:emote-sad-filled" /></template>
