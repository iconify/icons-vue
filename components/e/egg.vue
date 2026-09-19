<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1oyzrbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1oyzrbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:egg" /></template>
