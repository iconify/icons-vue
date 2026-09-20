<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr71j0btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qr71j0btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:infinity-16" /></template>
