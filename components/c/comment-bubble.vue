<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjdn7rc0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjdn7rc0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:comment-bubble" /></template>
