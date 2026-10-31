<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlixmjufr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tlixmjufr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:computer-laptop-solid" /></template>
