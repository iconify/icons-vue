<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob3i90--v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob3i90--v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:clock-three" /></template>
