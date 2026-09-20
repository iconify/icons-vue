<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx9a5uh8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zx9a5uh8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:itsm-ng" /></template>
