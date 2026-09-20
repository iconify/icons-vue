<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1db_x1ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="a1db_x1ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-logo-linkedin-network-linkedin-professional" /></template>
