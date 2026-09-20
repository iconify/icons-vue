<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfk_7v6jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mfk_7v6jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:globe-gasoline-pump-with-droplet" /></template>
