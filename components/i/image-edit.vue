<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ur1_bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ur1_bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-edit" /></template>
