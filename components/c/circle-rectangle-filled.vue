<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h88i13w-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h88i13w-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-rectangle-filled" /></template>
