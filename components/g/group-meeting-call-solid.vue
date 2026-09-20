<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h77_53wop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h77_53wop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:group-meeting-call-solid" /></template>
