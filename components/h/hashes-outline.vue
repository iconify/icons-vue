<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvx0o4p_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvx0o4p_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:hashes-outline" /></template>
