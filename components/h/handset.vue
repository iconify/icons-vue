<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlv67-bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wlv67-bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:handset" /></template>
