<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqfy4jbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="uqfy4jbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:livejournal" /></template>
