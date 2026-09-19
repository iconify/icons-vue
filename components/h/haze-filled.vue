<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbh13sb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rbh13sb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:haze-filled" /></template>
