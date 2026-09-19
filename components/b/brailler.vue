<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa28y5a1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="qa28y5a1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailler" /></template>
