<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b34_7zbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b34_7zbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart5-filled" /></template>
