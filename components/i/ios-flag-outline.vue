<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d35w0wbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d35w0wbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-flag-outline" /></template>
