<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc02_2oll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rc02_2oll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-up-outline" /></template>
