<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4csvlige.css';
import '../../css/y/y--a8-brh.css';
import '../../css/j/jap_-fj2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4csvlige"/><path class="y--a8-brh"/><path class="jap_-fj2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:earth-sharp" /></template>
