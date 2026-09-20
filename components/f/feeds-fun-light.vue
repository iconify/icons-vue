<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkleevbel.css';
import '../../css/k/koobuxbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkleevbel"/><path class="koobuxbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feeds-fun-light" /></template>
