<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfguy432a.css';
import '../../css/n/nhu-fkbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfguy432a"/><path class="nhu-fkbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flip-to-front-filled" /></template>
