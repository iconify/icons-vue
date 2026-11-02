<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acrf5cy9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acrf5cy9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-create-fill" /></template>
