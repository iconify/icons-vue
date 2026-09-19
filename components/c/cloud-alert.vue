<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygnd17bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygnd17bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-alert" /></template>
