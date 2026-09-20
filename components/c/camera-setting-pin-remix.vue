<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzg9ihbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzg9ihbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:camera-setting-pin-remix" /></template>
