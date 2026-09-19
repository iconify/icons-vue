<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou-xpxb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ou-xpxb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:enteralt" /></template>
