<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz-_htb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sz-_htb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hbo-light" /></template>
