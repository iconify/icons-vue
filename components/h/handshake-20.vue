<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3-_lcbqm.css';
import '../../css/w/w9b7p7brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s3-_lcbqm"/><path class="w9b7p7brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:handshake-20" /></template>
