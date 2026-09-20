<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sntofu_vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sntofu_vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:folder-add" /></template>
