<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5lnjuthr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5lnjuthr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:face-without-mouth-fill" /></template>
