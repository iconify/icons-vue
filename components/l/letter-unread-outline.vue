<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp2leebow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lp2leebow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-unread-outline" /></template>
