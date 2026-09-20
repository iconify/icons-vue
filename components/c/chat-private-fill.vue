<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o76epo28t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o76epo28t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-private-fill" /></template>
