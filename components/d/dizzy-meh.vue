<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngzxm-lii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngzxm-lii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dizzy-meh" /></template>
