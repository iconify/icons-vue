<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auleabc9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="auleabc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fire-alarm-1-solid" /></template>
