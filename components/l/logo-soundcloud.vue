<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu60_17re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu60_17re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-soundcloud" /></template>
