<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5lee5t5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5lee5t5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin" /></template>
