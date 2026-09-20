<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sns8z-bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sns8z-bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:joyful-filled" /></template>
