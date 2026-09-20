<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpodlbzms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpodlbzms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:golf-ball-fill" /></template>
