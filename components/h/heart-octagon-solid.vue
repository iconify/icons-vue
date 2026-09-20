<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-d4njw1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-d4njw1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-octagon-solid" /></template>
