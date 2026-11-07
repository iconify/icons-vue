<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b133qtshg.css';
import '../../css/o/oq5mzbcjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b133qtshg"/><path class="oq5mzbcjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-unread-bold-duotone" /></template>
