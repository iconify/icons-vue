<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrhv5lb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrhv5lb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:celery" /></template>
