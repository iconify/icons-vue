<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmqdbd-6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmqdbd-6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-plus-filled" /></template>
