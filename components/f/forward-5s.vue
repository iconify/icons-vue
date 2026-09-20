<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkw1efbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vkw1efbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-5s" /></template>
