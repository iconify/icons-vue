<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g69-czrme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g69-czrme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:clock" /></template>
