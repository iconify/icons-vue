<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr0xqpt6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sr0xqpt6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-zoom-in-bold" /></template>
