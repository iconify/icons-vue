<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq7w9gcux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq7w9gcux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-prime" /></template>
