<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iin_flbnk.css';
import '../../css/x/xvwzm4bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iin_flbnk"/><path class="xvwzm4bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitwarden" /></template>
