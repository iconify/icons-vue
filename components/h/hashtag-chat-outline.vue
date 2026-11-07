<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_vd_y58s.css';
import '../../css/j/jvqlzyq-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_vd_y58s"/><path clip-rule="evenodd" class="jvqlzyq-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-chat-outline" /></template>
