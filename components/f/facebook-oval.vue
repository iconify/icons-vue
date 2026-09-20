<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laa7w7bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="laa7w7bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:facebook-oval" /></template>
