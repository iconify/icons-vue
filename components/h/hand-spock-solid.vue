<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd6-75btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xd6-75btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-spock-solid" /></template>
