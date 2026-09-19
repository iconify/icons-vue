<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjh4gqbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjh4gqbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:eye-off" /></template>
