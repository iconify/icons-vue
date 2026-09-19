<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trtajbcie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="trtajbcie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:honeycomb" /></template>
