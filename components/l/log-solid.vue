<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l38cduphc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l38cduphc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:log-solid" /></template>
