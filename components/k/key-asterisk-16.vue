<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se52wg45h.css';
import '../../css/c/c38uaibrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="se52wg45h"/><path class="c38uaibrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:key-asterisk-16" /></template>
