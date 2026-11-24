<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr70wvhdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr70wvhdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:handshake-solid" /></template>
