<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgkeeod2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="dgkeeod2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:globe-africa" /></template>
