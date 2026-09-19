<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo4kztbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xo4kztbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:galaxy" /></template>
