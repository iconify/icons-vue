<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt-su-b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lt-su-b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:double-chevron-up" /></template>
