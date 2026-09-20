<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvaekkbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvaekkbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-password" /></template>
