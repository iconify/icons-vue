<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcpc8aclj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tcpc8aclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:8mb-local-light" /></template>
