<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl_3usbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xl_3usbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:grin2" /></template>
