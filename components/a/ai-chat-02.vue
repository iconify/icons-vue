<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocs53d2qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocs53d2qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-chat-02" /></template>
