<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcke9jbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bcke9jbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-kafka-light" /></template>
