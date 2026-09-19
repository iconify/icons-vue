<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_9dkpbmu.css';
import '../../css/o/o3b3gk40z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_9dkpbmu"/><path class="o3b3gk40z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:alarm-sharp" /></template>
