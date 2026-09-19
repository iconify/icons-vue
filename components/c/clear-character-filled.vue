<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmshvrgkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmshvrgkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:clear-character-filled" /></template>
