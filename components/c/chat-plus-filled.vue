<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azp4bzbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="azp4bzbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-plus-filled" /></template>
