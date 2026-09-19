<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjankhbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjankhbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-ekm" /></template>
