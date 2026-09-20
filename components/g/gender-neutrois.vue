<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fugyre1oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fugyre1oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-neutrois" /></template>
