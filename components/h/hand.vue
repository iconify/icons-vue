<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjuinsb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjuinsb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand" /></template>
