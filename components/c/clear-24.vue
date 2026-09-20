<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvhzlphhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvhzlphhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:clear-24" /></template>
