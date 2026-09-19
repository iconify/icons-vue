<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwp_pubaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1024};
const content = `<path class="xwp_pubaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:extinguisher" /></template>
