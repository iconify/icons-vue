<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_0em7blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_0em7blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-v-octagon-solid" /></template>
