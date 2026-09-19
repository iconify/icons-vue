<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mny56ybxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mny56ybxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-code-filled" /></template>
