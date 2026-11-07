<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b133qtshg.css';
import '../../css/a/aoju1jbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b133qtshg"/><path class="aoju1jbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-unread-bold-duotone" /></template>
