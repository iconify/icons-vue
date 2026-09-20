<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvk2zxd-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tvk2zxd-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:2fauth" /></template>
