<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mox62k4cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mox62k4cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cooklang-chef-light" /></template>
