<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huizebc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huizebc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:database-alt" /></template>
