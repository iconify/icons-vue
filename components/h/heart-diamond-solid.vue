<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-_f9rb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-_f9rb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-diamond-solid" /></template>
