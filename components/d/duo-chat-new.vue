<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzb7ntb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xzb7ntb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:duo-chat-new" /></template>
