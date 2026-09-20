<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li7an9b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="li7an9b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hat-fill" /></template>
