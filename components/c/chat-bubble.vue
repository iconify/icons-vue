<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdahbrsqi.css';
import '../../css/z/zt1dysdrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdahbrsqi"/><path class="zt1dysdrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chat-bubble" /></template>
