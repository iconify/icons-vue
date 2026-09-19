<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e31tmz-oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e31tmz-oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:magic" /></template>
