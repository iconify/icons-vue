<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgazo6tfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mgazo6tfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:linkedin-solid" /></template>
