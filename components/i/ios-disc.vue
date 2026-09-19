<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxx4v7bby.css';
import '../../css/s/snz1cvidd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxx4v7bby"/><path class="snz1cvidd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-disc" /></template>
