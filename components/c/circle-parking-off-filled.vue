<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qevsu6brs.css';
import '../../css/w/wfk--dl3u.css';
import '../../css/v/vgshsqbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qevsu6brs"/><path class="wfk--dl3u"/><path class="vgshsqbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-parking-off-filled" /></template>
