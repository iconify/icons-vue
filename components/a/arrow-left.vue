<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sich1rccl.css';
import '../../css/p/p4luhxbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sich1rccl"/><path class="p4luhxbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:arrow-left" /></template>
