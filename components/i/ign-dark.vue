<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs2fs5bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bs2fs5bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ign-dark" /></template>
