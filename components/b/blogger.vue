<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f925hvu6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f925hvu6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:blogger" /></template>
