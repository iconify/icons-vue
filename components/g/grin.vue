<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2f8t22k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="rp2f8t22k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin" /></template>
