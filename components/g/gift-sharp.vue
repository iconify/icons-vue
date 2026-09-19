<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4lrn5gzp.css';
import '../../css/s/skk-_uu3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4lrn5gzp"/><path class="skk-_uu3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:gift-sharp" /></template>
