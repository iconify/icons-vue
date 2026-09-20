<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-zudbcoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-zudbcoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:base-ui" /></template>
