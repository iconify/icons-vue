<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9m4smbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9m4smbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-left-fill" /></template>
