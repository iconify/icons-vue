<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqzrj90_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqzrj90_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:align-center-v" /></template>
