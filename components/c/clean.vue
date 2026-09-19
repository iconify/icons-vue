<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av0n4_bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":319,"height":512};
const content = `<path class="av0n4_bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:clean" /></template>
