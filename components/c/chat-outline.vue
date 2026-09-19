<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf6woy2-u.css';
import '../../css/m/mr124pbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf6woy2-u"/><path clip-rule="evenodd" class="mr124pbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:chat-outline" /></template>
