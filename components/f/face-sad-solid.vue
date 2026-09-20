<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly7ntacbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly7ntacbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-sad-solid" /></template>
