<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-efg3ywk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="b-efg3ywk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:armrecording" /></template>
