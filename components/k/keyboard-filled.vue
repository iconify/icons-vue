<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br9gtx66z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="br9gtx66z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:keyboard-filled" /></template>
