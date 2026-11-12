<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_eb1s5-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_eb1s5-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubernetes-light" /></template>
