<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5uu06nhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5uu06nhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:aruba" /></template>
