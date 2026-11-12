<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri3z_o84b.css';
import '../../css/d/dghaoubtt.css';
import '../../css/f/fu8qg7bvm.css';
import '../../css/f/f4-o-bcct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri3z_o84b"/><path class="dghaoubtt"/><path class="fu8qg7bvm"/><path class="f4-o-bcct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ente-photos-light" /></template>
