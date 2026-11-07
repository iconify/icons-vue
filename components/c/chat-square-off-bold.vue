<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erra6gogy.css';
import '../../css/i/ix_x8gb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erra6gogy"/><path class="ix_x8gb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-off-bold" /></template>
