<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soy-_013u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soy-_013u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left" /></template>
