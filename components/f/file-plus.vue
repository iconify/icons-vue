<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4g3jngnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4g3jngnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:file-plus" /></template>
