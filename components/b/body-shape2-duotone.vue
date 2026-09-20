<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v35r45b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v35r45b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:body-shape2-duotone" /></template>
