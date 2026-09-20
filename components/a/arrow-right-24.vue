<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amsxbvear.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amsxbvear"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-right-24" /></template>
