<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym2po6bfu.css';
import '../../css/g/g_ffjxz3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym2po6bfu"/><path class="g_ffjxz3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-setting-filled" /></template>
