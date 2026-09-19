<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdvm4wbmz.css';
import '../../css/j/ji70huh2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hdvm4wbmz"/><path class="ji70huh2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:couchbase-wordmark" /></template>
