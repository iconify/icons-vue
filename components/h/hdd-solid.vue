<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2p3ih6-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k2p3ih6-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hdd-solid" /></template>
