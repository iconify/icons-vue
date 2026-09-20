<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtjbmczta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="wtjbmczta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:extinguisher-f" /></template>
