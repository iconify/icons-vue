<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6gs46bps.css';
import '../../css/f/fi3u09b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6gs46bps"/><path class="fi3u09b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-plus-corner-filled" /></template>
