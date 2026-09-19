<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5f3b3qcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="y5f3b3qcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-stars" /></template>
