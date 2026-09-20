<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-nlyrbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u-nlyrbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:internal-medicine" /></template>
