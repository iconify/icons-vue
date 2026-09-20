<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx__e5bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx__e5bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:emoji-funny-square-bold" /></template>
