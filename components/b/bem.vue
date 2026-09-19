<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfk3trb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfk3trb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bem" /></template>
