<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b505crlwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b505crlwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:archive-tick-filled" /></template>
