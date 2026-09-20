<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-4e5pb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-4e5pb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:attic-1-filled" /></template>
