<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz-3k2cdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz-3k2cdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dell" /></template>
