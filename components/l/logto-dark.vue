<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8nfsfvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ba8nfsfvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logto-dark" /></template>
