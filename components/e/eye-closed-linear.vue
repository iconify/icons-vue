<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3vf0gi4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3vf0gi4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-closed-linear" /></template>
