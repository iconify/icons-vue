<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1tnuqmcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1tnuqmcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:insecure" /></template>
