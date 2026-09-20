<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqarkh7mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqarkh7mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:jcb" /></template>
