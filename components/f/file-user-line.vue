<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ofpun1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0ofpun1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-user-line" /></template>
