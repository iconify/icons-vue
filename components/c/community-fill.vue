<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gojobqb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gojobqb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:community-fill" /></template>
