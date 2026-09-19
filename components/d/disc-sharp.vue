<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1bg4hbvb.css';
import '../../css/i/i5e6rm6wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="a1bg4hbvb"/><path class="i5e6rm6wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:disc-sharp" /></template>
