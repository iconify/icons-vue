<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk6o28bka.css';
import '../../css/c/c991nybxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qk6o28bka"/><path class="c991nybxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-auto-light" /></template>
