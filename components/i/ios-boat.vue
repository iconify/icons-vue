<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_k7_fb0a.css';
import '../../css/h/hrwuikbxl.css';
import '../../css/o/olalq2vor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_k7_fb0a"/><path class="hrwuikbxl"/><path class="olalq2vor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-boat" /></template>
