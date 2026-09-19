<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu9iqqbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu9iqqbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:face-smile-solid" /></template>
