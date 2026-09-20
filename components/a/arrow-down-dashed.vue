<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h10vd1ynh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h10vd1ynh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-dashed" /></template>
