<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5kqz9n5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5kqz9n5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crown-circle-outline" /></template>
