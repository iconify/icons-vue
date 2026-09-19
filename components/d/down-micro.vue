<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3vg0rc7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":471,"height":1000};
const content = `<path class="s3vg0rc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:down-micro" /></template>
