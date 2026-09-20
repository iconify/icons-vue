<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im9faeila.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im9faeila"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-3-bold" /></template>
