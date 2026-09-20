<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb2p06bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb2p06bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-slash-solid" /></template>
