<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs166ab5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs166ab5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eight-ball" /></template>
