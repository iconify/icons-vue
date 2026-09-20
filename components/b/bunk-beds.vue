<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbznzrb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jbznzrb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bunk-beds" /></template>
