<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b103epbdu.css';
import '../../css/w/wre6mlbjq.css';
import '../../css/c/cz6z9n00t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b103epbdu"/><path class="wre6mlbjq"/><path class="cz6z9n00t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:colota-dark" /></template>
