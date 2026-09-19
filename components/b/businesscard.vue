<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvj-cvb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="xvj-cvb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:businesscard" /></template>
