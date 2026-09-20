<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrvgcksgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lrvgcksgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grapheneos-dark" /></template>
