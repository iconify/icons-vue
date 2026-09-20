<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcs-u5b0a.css';
import '../../css/k/kf0teob-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcs-u5b0a"/><path class="kf0teob-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mail-filled" /></template>
