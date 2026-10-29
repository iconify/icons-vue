<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ky4acxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-ky4acxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key-round-solid" /></template>
