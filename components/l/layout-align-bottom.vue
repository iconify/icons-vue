<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6j4ececu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6j4ececu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-bottom" /></template>
