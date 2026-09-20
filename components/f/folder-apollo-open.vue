<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_02szb5c.css';
import '../../css/t/tw_m98bcm.css';
import '../../css/f/fgnd1rb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q_02szb5c"/><path class="tw_m98bcm"/><path class="fgnd1rb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-apollo-open" /></template>
