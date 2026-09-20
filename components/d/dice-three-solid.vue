<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxxzwsd3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxxzwsd3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-three-solid" /></template>
