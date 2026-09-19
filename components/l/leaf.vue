<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc2w2q85y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rc2w2q85y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:leaf" /></template>
