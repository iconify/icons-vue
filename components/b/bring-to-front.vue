<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4vawjbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4vawjbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bring-to-front" /></template>
