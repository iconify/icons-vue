<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufjg9-beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufjg9-beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jsr" /></template>
