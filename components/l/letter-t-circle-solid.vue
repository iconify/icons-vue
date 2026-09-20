<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2velv8sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2velv8sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-circle-solid" /></template>
