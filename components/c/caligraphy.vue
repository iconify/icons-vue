<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbgjb1_vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fbgjb1_vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:caligraphy" /></template>
