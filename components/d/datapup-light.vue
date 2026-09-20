<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5yk22b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5yk22b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:datapup-light" /></template>
