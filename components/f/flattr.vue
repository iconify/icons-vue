<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukqdl4brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukqdl4brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:flattr" /></template>
