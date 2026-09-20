<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spzjxlbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="spzjxlbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-filled-alt-fill" /></template>
