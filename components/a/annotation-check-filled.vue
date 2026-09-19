<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqwqyzbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqwqyzbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:annotation-check-filled" /></template>
