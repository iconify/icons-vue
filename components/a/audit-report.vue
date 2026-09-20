<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flqx9-u3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="flqx9-u3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:audit-report" /></template>
