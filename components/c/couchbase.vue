<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa-m42b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sa-m42b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:couchbase" /></template>
