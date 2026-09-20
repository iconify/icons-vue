<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox-rx1bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ox-rx1bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-nursery" /></template>
