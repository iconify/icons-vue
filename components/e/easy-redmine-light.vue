<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po3mlvuua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="po3mlvuua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:easy-redmine-light" /></template>
