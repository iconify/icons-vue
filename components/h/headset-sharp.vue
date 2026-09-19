<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3g6tym6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3g6tym6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:headset-sharp" /></template>
