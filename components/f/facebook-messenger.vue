<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzzo6jbar.css';
import '../../css/f/fnt2v3b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yzzo6jbar"/><path class="fnt2v3b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:facebook-messenger" /></template>
