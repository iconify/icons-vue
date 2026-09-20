<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne8-4acba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ne8-4acba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:brush" /></template>
