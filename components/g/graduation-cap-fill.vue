<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha10fqvhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha10fqvhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:graduation-cap-fill" /></template>
