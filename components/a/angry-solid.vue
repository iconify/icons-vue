<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h74ufob4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h74ufob4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:angry-solid" /></template>
