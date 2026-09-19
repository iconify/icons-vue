<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lotbarb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lotbarb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lgtm" /></template>
