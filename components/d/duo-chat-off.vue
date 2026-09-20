<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtp_8xwkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gtp_8xwkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:duo-chat-off" /></template>
